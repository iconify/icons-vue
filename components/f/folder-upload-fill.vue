<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx_0ltekc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx_0ltekc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-upload-fill" /></template>
