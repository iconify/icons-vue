<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y892mo3mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y892mo3mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pyramid-sharp" /></template>
