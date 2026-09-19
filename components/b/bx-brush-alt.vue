<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb5kezbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb5kezbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-brush-alt" /></template>
