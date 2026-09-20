<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb_4tt4ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_4tt4ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:floatplane" /></template>
