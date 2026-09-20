<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdhhtkvfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhhtkvfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:file-upload-line" /></template>
