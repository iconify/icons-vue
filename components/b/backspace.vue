<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpv1xwoom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpv1xwoom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:backspace" /></template>
