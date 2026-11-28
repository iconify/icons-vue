<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxgpe524t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxgpe524t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cooking-pot-plus" /></template>
