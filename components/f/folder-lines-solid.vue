<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ienhyphke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ienhyphke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-lines-solid" /></template>
