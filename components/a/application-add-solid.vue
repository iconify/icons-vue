<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st4w9dbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="st4w9dbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:application-add-solid" /></template>
