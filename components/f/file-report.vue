<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5d7qab8q.css';
import '../../css/j/j4nbmzbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5d7qab8q"/><path class="j4nbmzbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-report" /></template>
