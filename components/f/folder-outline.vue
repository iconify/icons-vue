<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odku5czbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odku5czbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-outline" /></template>
