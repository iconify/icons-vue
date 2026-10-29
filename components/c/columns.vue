<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojz-7nhbw.css';
import '../../css/z/zr7zg75lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojz-7nhbw"/><path class="zr7zg75lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:columns" /></template>
