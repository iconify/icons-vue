<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdu8ar_ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sdu8ar_ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-upload" /></template>
