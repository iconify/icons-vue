<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4-a4tbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4-a4tbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:inbox-24" /></template>
