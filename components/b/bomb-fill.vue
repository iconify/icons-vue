<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3mt6e6zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3mt6e6zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bomb-fill" /></template>
