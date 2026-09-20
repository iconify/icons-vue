<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_khmlbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_khmlbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hbo-max-light" /></template>
