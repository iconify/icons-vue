<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkqcgcbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkqcgcbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ctt" /></template>
