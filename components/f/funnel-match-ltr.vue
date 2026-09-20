<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gac1gm6_a.css';
import '../../css/l/lf-esqlup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gac1gm6_a"/><path class="lf-esqlup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:funnel-match-ltr" /></template>
