<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkq108bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkq108bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bell-info" /></template>
