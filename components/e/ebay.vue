<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb_uf5bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb_uf5bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ebay" /></template>
