<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg32huyrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg32huyrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eagle-round" /></template>
