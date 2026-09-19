<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4d0o9i5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4d0o9i5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrows-vertical" /></template>
