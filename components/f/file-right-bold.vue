<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhj7tk-5q.css';
import '../../css/p/ppeku0kau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path clip-rule="evenodd" class="ppeku0kau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-right-bold" /></template>
