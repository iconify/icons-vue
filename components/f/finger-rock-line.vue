<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwt7q8brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwt7q8brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-rock-line" /></template>
