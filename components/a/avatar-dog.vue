<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vsusckuge.css';
import '../../css/v/vryyh5bgx.css';
import '../../css/h/h-9fzqies.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vsusckuge"/><path class="vryyh5bgx"/><path class="h-9fzqies wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-dog" /></template>
