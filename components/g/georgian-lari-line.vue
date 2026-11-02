<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhteuhbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhteuhbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:georgian-lari-line" /></template>
