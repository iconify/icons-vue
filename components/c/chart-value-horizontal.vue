<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agfkxsk5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="agfkxsk5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-value-horizontal" /></template>
