<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyayll8ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyayll8ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:facebook" /></template>
