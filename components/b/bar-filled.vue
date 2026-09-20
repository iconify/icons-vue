<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3557nbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h3557nbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bar-filled" /></template>
