<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3rqy3bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w3rqy3bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dot-circle-solid" /></template>
