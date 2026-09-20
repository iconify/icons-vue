<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhji1fb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qhji1fb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dochub" /></template>
