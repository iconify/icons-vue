<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3nypc2-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3nypc2-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-del" /></template>
