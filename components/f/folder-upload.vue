<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb-54sz4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb-54sz4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-upload" /></template>
