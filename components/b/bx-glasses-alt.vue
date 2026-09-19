<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovau7gmyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovau7gmyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-glasses-alt" /></template>
