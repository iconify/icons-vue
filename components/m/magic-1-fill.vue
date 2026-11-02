<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaiydvbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaiydvbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-1-fill" /></template>
