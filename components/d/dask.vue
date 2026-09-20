<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmjd6gzzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjd6gzzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dask" /></template>
