<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h93r4zbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h93r4zbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email" /></template>
