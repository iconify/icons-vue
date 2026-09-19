<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt3vx2b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jt3vx2b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:at-circle-fill" /></template>
