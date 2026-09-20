<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxnd1vbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxnd1vbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-down" /></template>
