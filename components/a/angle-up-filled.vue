<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arpkf7b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arpkf7b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:angle-up-filled" /></template>
