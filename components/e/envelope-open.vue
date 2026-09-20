<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/int9g14to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="int9g14to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-open" /></template>
