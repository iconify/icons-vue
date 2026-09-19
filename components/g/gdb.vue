<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkk121bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mkk121bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gdb" /></template>
