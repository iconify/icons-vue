<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trg_kpbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="trg_kpbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-download-solid" /></template>
