<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvzp0ac7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvzp0ac7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top-right-filled" /></template>
