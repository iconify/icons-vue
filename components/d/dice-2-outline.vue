<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvmsos8ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvmsos8ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-2-outline" /></template>
