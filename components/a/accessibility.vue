<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-my5lk7s.css';
import '../../css/g/g8crnxb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o-my5lk7s"/><path class="g8crnxb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:accessibility" /></template>
