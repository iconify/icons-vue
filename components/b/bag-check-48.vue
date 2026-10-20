<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2gho-_w.css';
import '../../css/z/ztjblhbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb2gho-_w"/><path class="ztjblhbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-check-48" /></template>
