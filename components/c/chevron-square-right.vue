<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc0t7rxjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="lc0t7rxjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-square-right" /></template>
