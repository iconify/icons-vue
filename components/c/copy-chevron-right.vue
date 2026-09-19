<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgzm9feoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hgzm9feoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy-chevron-right" /></template>
