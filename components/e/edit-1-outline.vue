<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgxcpmbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qgxcpmbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-1-outline" /></template>
