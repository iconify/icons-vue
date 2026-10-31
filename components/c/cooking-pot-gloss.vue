<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow11ylbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow11ylbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cooking-pot-gloss" /></template>
