<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu20pdb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu20pdb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-dashed-panel" /></template>
