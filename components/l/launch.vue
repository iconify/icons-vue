<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6kb-tklu.css';
import '../../css/s/s6r4foaoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n6kb-tklu"/><path class="s6r4foaoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:launch" /></template>
