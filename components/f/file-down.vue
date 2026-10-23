<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zehk59bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zehk59bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-down" /></template>
