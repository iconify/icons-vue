<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj97e-e8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj97e-e8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:anchor" /></template>
