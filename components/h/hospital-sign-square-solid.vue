<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd7nbrfem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hd7nbrfem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hospital-sign-square-solid" /></template>
