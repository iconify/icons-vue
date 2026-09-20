<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahkce2-8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahkce2-8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:brackets" /></template>
