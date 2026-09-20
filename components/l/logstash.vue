<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjj5xkb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjj5xkb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:logstash" /></template>
