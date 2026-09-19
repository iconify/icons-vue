<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm7he-b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mm7he-b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-record" /></template>
