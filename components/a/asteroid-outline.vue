<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvktin_ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvktin_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:asteroid-outline" /></template>
