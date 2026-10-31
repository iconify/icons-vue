<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p44ku7_ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p44ku7_ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:keyboard" /></template>
