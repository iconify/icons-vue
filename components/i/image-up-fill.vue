<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geb6jiw3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geb6jiw3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-up-fill" /></template>
