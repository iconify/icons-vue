<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beiwgnruu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beiwgnruu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:four-wheel-drive-line" /></template>
