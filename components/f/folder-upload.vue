<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g50cx0bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g50cx0bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-upload" /></template>
