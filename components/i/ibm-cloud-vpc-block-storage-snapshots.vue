<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3jzubbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y3jzubbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-vpc-block-storage-snapshots" /></template>
