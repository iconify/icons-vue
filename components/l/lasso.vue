<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvnt-8bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nvnt-8bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lasso" /></template>
