<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfo9l1-9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zfo9l1-9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:jedi" /></template>
