<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvatv5_qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvatv5_qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-bollard-wall-appear" /></template>
