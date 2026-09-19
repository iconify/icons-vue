<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzbgldeoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzbgldeoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:help-octagon-filled" /></template>
