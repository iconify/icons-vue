<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouah7nb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ouah7nb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:font-cursor" /></template>
