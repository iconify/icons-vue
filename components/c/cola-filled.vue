<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufphf7byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufphf7byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cola-filled" /></template>
