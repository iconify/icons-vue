<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jek30jwcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jek30jwcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:backward-end" /></template>
