<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-l2srbfo.css';
import '../../css/m/m-ub-lbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-l2srbfo"/><path clip-rule="evenodd" class="m-ub-lbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bus-front-filled" /></template>
