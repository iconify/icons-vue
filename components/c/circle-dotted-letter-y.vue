<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6-gxwehl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-gxwehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-y" /></template>
