<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqcxcrapc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqcxcrapc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:firefly-iii" /></template>
