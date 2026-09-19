<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmwn0h9_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmwn0h9_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:import" /></template>
