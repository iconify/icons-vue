<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jux9gab8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="jux9gab8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:eye" /></template>
