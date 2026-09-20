<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1j74k3mk.css';
import '../../css/g/gknbh0bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="y1j74k3mk"/><path class="gknbh0bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:atom" /></template>
