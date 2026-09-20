<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb9onsblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb9onsblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-edit" /></template>
