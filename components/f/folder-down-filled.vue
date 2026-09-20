<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f328ledil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f328ledil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-down-filled" /></template>
