<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okk6ekkxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1280};
const content = `<path class="okk6ekkxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:ellipsis-h" /></template>
