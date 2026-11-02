<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mezec7btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mezec7btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:documents-fill" /></template>
