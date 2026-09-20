<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo81fmntw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo81fmntw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-none-line" /></template>
