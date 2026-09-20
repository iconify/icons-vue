<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juzj7mbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juzj7mbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layers-one-solid" /></template>
