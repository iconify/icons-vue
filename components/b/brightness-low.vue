<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i08v84bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i08v84bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:brightness-low" /></template>
