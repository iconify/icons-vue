<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_qbl-6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md_qbl-6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:banknote-outline" /></template>
