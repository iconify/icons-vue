<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f58w969ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f58w969ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-json-gloss" /></template>
