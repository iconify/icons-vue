<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_a7_nbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_a7_nbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-filled" /></template>
