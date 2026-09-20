<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb1geub1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb1geub1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-circle" /></template>
