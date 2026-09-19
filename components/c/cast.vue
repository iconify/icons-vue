<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zudyo4p4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="zudyo4p4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cast" /></template>
