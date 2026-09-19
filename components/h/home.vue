<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6u2o4t9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6u2o4t9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:home" /></template>
