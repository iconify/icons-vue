<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbtsfbb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gbtsfbb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:files" /></template>
