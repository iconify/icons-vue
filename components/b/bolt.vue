<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ascqfcb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ascqfcb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bolt" /></template>
