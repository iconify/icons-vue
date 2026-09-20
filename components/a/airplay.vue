<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr2j3nbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2j3nbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:airplay" /></template>
