<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrw0n8ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pwrw0n8ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:bity" /></template>
