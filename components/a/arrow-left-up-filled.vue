<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2cw0abjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2cw0abjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-up-filled" /></template>
