<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9oq7nbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9oq7nbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fluval-logo" /></template>
