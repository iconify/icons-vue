<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g775v9b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="g775v9b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:dot-circle-o" /></template>
