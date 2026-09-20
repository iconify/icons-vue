<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c054pcbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c054pcbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-import" /></template>
