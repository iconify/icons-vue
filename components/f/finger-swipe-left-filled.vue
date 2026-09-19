<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcf2g90wf.css';
import '../../css/g/gfumbbcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcf2g90wf"/><path class="gfumbbcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-left-filled" /></template>
