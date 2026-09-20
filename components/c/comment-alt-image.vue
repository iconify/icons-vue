<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_8ypwbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8ypwbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-image" /></template>
