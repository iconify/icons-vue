<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb178zbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb178zbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:json" /></template>
