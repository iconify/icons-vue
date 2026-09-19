<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9g1qcbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9g1qcbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:anchor" /></template>
