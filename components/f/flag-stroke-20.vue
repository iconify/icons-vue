<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcsx0bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ezcsx0bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-stroke-20" /></template>
