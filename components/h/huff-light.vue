<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-29-dopm.css';
import '../../css/o/okgd0ab2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="z-29-dopm"/><path class="okgd0ab2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:huff-light" /></template>
