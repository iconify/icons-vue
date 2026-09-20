<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnpb948yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnpb948yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-right-sharp-fill" /></template>
