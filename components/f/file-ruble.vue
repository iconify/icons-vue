<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm-omubpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xm-omubpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-ruble" /></template>
