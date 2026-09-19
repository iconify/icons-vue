<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxjodwbrk.css';
import '../../css/e/e132nkbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxjodwbrk"/><path class="e132nkbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:cloud-upload-outline" /></template>
