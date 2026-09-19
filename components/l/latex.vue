<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfsz5_b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nfsz5_b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:latex" /></template>
