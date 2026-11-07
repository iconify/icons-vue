<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1jlu27kk.css';
import '../../css/d/dnv52pbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jlu27kk"/><path class="dnv52pbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-right-left-bold" /></template>
