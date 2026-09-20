<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsljxnill.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsljxnill"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:folder-1" /></template>
