<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o57oqtj-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o57oqtj-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-rocket" /></template>
