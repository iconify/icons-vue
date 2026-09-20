<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmfvf21cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vmfvf21cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:align-right-flat" /></template>
