<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e11cv8b-r.css';
import '../../css/r/rgvk_601g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e11cv8b-r"/><path class="rgvk_601g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:check-square-bold" /></template>
