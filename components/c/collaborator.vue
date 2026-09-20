<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbf_zkbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="zbf_zkbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:collaborator" /></template>
