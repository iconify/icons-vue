<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3uj0ccyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3uj0ccyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-close-bold" /></template>
