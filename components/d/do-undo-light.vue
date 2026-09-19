<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-nmp8oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-nmp8oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-undo-light" /></template>
