<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6dx8-byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6dx8-byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-heart-filled" /></template>
