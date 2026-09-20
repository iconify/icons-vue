<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsmgo6kln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsmgo6kln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-expansion-filled" /></template>
