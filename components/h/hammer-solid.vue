<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ia8gbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e0ia8gbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hammer-solid" /></template>
