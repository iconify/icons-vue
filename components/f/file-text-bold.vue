<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1g98hbyj.css';
import '../../css/r/rhj7tk-5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1g98hbyj"/><path class="rhj7tk-5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-text-bold" /></template>
