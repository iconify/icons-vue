<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frjdkl5gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="frjdkl5gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-up-solid" /></template>
