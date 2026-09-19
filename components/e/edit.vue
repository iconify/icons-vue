<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5racfbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y5racfbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:edit" /></template>
