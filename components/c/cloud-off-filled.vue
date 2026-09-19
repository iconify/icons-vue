<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf5_zmbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uf5_zmbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloud-off-filled" /></template>
