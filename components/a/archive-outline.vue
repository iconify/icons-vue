<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cerp1lnii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cerp1lnii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:archive-outline" /></template>
