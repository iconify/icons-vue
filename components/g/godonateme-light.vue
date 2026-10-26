<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktv0erbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ktv0erbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:godonateme-light" /></template>
