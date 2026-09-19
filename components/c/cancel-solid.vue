<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahzihro8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ahzihro8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cancel-solid" /></template>
