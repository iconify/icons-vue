<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r51afdcqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r51afdcqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-upload-x" /></template>
