<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi_hcp08f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mi_hcp08f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:backward-start-circle" /></template>
