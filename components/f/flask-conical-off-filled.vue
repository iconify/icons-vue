<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th8n30upe.css';
import '../../css/m/mjdzrmbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th8n30upe"/><path class="mjdzrmbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flask-conical-off-filled" /></template>
