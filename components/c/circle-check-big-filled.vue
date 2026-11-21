<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhi8lybtb.css';
import '../../css/l/lgjscu5ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhi8lybtb"/><path class="lgjscu5ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-check-big-filled" /></template>
