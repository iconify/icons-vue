<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4p2dtbwt.css';
import '../../css/i/ia-bsrbll.css';
import '../../css/b/bog62tbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4p2dtbwt"/><path class="ia-bsrbll"/><path class="bog62tbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:images" /></template>
