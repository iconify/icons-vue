<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7fla1l-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7fla1l-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:attachment-01" /></template>
