<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggbg5jbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbg5jbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:anthropic" /></template>
