<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvf-d1baf.css';
import '../../css/c/cs8o81b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvf-d1baf"/><path class="cs8o81b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lightbulb-off-filled" /></template>
