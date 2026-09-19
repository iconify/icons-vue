<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iugo9tbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iugo9tbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:app-store" /></template>
