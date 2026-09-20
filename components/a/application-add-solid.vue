<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9owu2hrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s9owu2hrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:application-add-solid" /></template>
