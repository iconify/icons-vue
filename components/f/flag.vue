<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8psg-zwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8psg-zwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:flag" /></template>
