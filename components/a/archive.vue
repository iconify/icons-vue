<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v38xawbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v38xawbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:archive" /></template>
