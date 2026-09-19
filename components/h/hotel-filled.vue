<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldbuywl5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldbuywl5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hotel-filled" /></template>
