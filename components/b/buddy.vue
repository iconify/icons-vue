<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe_9sqb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qe_9sqb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:buddy" /></template>
