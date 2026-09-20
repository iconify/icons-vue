<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka5_0n05d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka5_0n05d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-exclamation" /></template>
