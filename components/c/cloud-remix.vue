<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eawg9ib8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eawg9ib8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cloud-remix" /></template>
