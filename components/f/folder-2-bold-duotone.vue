<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pteai7udj.css';
import '../../css/k/kvtxzidpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pteai7udj"/><path class="kvtxzidpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-2-bold-duotone" /></template>
