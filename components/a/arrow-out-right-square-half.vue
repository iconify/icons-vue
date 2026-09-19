<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgz295blo.css';
import '../../css/g/g_z5fgbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgz295blo"/><path class="g_z5fgbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-right-square-half" /></template>
