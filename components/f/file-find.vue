<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2nszzb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2nszzb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:file-find" /></template>
