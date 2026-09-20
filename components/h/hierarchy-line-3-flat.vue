<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv0qhybxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bv0qhybxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:hierarchy-line-3-flat" /></template>
