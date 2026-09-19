<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5eun5bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5eun5bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dodge" /></template>
