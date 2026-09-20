<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_cgil99b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_cgil99b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-2-fill" /></template>
