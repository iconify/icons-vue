<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unc3p6dyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unc3p6dyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:inquiry-mail" /></template>
