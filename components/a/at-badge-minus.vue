<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ussur-5ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ussur-5ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:at-badge-minus" /></template>
