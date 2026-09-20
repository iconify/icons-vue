<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2nt4m_0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2nt4m_0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-3" /></template>
