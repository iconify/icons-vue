<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfgw7gb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zfgw7gb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy-plus" /></template>
