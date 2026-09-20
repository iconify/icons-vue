<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg1mfnptg.css';
import '../../css/l/l6wc1bw2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1mfnptg"/><path class="l6wc1bw2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:browser-com-bold" /></template>
