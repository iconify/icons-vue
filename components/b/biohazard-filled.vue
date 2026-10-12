<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2l34ybtf.css';
import '../../css/j/j8cdfd2tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2l34ybtf"/><path class="j8cdfd2tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:biohazard-filled" /></template>
