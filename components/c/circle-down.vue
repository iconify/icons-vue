<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwuk1ybsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwuk1ybsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-down" /></template>
