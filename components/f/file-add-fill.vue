<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq0e4bhuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq0e4bhuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-add-fill" /></template>
