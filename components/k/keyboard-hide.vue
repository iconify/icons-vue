<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm7p86bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm7p86bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:keyboard-hide" /></template>
