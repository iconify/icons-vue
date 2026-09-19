<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh4ur_bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xh4ur_bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-descending-align-center" /></template>
