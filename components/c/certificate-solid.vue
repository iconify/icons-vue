<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mco3pablm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mco3pablm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:certificate-solid" /></template>
