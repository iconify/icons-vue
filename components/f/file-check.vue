<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob61d0b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ob61d0b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-check" /></template>
