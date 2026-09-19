<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxxysjz2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zxxysjz2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-a-z" /></template>
