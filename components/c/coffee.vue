<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p80j4lbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p80j4lbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:coffee" /></template>
