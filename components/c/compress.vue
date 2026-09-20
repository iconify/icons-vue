<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay6-rac8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay6-rac8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:compress" /></template>
