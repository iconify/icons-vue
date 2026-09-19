<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8dlvpbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8dlvpbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-fill" /></template>
