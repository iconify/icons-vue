<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x67qmvbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x67qmvbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grass-solid" /></template>
