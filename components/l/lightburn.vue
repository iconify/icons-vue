<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyhxlib4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhxlib4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lightburn" /></template>
