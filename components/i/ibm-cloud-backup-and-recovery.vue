<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6n2pebht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b6n2pebht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-backup-and-recovery" /></template>
