<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj2b-d93h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2b-d93h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bmw-alt" /></template>
