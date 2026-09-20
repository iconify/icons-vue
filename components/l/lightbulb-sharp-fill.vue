<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk_47gbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_47gbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lightbulb-sharp-fill" /></template>
