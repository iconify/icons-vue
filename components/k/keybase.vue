<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_r27j01j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":512};
const content = `<path clip-rule="evenodd" class="t_r27j01j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:keybase" /></template>
