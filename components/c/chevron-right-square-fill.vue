<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjo89i77m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gjo89i77m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-right-square-fill" /></template>
