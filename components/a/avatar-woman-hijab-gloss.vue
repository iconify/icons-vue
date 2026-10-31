<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc41uk-dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc41uk-dj wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-hijab-gloss" /></template>
