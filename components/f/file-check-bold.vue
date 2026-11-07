<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhj7tk-5q.css';
import '../../css/h/h4-0w54pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path clip-rule="evenodd" class="h4-0w54pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-check-bold" /></template>
