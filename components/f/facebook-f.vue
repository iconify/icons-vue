<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qye3bdb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qye3bdb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:facebook-f" /></template>
