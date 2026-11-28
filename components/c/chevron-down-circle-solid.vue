<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkn55lbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkn55lbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-down-circle-solid" /></template>
