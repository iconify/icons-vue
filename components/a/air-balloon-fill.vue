<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbdsgt3gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbdsgt3gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-balloon-fill" /></template>
