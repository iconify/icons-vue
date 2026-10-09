<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy7xqk_um.css';
import '../../css/e/esgmmdbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="esgmmdbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:columns-48-bold" /></template>
