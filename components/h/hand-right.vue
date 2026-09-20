<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqdgb1rqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqdgb1rqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-right" /></template>
