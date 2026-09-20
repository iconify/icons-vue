<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzy3gmb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzy3gmb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:chevron-down" /></template>
