<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzu0pmlpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzu0pmlpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-dot-solid" /></template>
