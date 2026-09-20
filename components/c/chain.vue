<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpe14k1eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpe14k1eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:chain" /></template>
