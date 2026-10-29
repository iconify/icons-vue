<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9ssqz_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9ssqz_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:git-fork" /></template>
