<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6fsyy90t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1408};
const content = `<path class="z6fsyy90t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:beer" /></template>
