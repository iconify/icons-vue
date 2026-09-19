<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo7c1d9kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uo7c1d9kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-square-fill" /></template>
