<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtdmv7zzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtdmv7zzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-outline" /></template>
