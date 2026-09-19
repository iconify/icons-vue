<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpa-aachc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpa-aachc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-justify-center" /></template>
