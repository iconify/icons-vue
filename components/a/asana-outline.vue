<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zztt8vqsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zztt8vqsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:asana-outline" /></template>
