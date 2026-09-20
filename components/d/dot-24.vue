<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmrwjd4ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmrwjd4ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dot-24" /></template>
