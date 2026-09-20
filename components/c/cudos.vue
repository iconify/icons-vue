<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_at2po4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_at2po4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cudos" /></template>
