<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ff2wuha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ff2wuha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-user-solid" /></template>
