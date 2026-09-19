<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es9czvboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="es9czvboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:logstash" /></template>
