<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_4tjt7gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e_4tjt7gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:etsy" /></template>
