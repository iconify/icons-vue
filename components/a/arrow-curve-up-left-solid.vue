<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajkar9b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajkar9b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-left-solid" /></template>
