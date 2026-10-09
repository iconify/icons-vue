<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkwxxqb3q.css';
import '../../css/f/f6w9iq-hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="f6w9iq-hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copper-20-bold" /></template>
