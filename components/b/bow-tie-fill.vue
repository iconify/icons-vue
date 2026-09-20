<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln5cit_qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln5cit_qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bow-tie-fill" /></template>
