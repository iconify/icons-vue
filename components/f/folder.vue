<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h28_f0buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h28_f0buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder" /></template>
