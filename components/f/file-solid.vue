<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7p86sb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7p86sb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-solid" /></template>
