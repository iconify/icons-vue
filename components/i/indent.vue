<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s656amszl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s656amszl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:indent" /></template>
