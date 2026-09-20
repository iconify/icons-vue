<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3z_4ymzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t3z_4ymzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bimobject" /></template>
