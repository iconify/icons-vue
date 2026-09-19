<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by-oj7bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="by-oj7bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:laravel" /></template>
