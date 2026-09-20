<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4v9t2bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4v9t2bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:handshake" /></template>
