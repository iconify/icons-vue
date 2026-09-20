<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swifegtcy.css';
import '../../css/f/falyj_29j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="swifegtcy"/><path class="falyj_29j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-custom-open" /></template>
