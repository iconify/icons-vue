<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yobm0iblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yobm0iblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dice-d6" /></template>
