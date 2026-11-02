<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqqx58b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqqx58b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-hat-2-fill" /></template>
