<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo8v5jbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bo8v5jbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-pdf-fill-12" /></template>
