<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3nvt0jim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="s3nvt0jim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:cloud-alt" /></template>
