<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-_e-j4zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_e-j4zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-sparkle" /></template>
