<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wysaowb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wysaowb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-person-arms-spread-filled" /></template>
