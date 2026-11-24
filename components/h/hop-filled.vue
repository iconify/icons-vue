<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzj6aoylk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzj6aoylk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hop-filled" /></template>
