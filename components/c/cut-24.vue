<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyjin6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyjin6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cut-24" /></template>
