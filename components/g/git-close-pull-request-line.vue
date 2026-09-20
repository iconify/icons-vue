<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otv5c1bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otv5c1bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-close-pull-request-line" /></template>
