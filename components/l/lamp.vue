<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs7942tbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs7942tbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lamp" /></template>
