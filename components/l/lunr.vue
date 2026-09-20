<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5v6j8bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5v6j8bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lunr" /></template>
