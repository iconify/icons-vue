<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxxk3-bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxxk3-bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-share" /></template>
