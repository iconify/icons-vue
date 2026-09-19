<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsmu52gdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="xsmu52gdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fax" /></template>
