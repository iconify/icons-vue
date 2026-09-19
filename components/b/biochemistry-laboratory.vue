<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq2-ldpak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nq2-ldpak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:biochemistry-laboratory" /></template>
