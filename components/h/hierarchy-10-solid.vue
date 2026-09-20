<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gok03r4yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gok03r4yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-10-solid" /></template>
