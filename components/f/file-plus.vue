<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d934pabiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d934pabiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-plus" /></template>
