<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afgl2wb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afgl2wb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-alt-2-filled" /></template>
