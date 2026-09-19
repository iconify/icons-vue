<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8ou37b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="q8ou37b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:file-alt" /></template>
