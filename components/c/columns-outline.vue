<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwsk7dcmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwsk7dcmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:columns-outline" /></template>
