<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hww7bvv-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hww7bvv-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brush-filled" /></template>
