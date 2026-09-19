<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba6_olbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ba6_olbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy" /></template>
