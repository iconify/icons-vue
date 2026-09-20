<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwpj51bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fwpj51bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flush-curb" /></template>
