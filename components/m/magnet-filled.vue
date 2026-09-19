<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck2oebwzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck2oebwzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:magnet-filled" /></template>
