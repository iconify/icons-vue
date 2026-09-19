<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6lc9cc4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6lc9cc4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:blockchain" /></template>
