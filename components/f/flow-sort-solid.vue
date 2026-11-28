<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd4jgsgnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4jgsgnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-sort-solid" /></template>
