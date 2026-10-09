<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv1fucc3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hv1fucc3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anvil-20-bold" /></template>
