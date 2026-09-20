<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sujk3jbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sujk3jbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:anchor" /></template>
