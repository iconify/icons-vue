<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4sr2psho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4sr2psho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-cog-solid" /></template>
