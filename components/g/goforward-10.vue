<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydmk_8akd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ydmk_8akd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-10" /></template>
