<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96xjgbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v96xjgbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:horse" /></template>
