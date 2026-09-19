<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oovqvoxkv.css';
import '../../css/k/k_u3wubkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oovqvoxkv"/><path class="k_u3wubkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:compass-fill" /></template>
