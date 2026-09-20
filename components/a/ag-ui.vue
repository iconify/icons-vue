<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4ovl2bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4ovl2bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ag-ui" /></template>
