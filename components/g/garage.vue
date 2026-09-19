<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xenb6xnsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="xenb6xnsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:garage" /></template>
