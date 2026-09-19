<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajl8h9bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajl8h9bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fexl" /></template>
