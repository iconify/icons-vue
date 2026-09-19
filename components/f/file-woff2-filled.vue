<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg9m1iqrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fg9m1iqrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff2-filled" /></template>
