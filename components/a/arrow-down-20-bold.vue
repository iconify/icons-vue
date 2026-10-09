<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjx8q2jsf.css';
import '../../css/j/jwge04g2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jjx8q2jsf"/><path class="jwge04g2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-20-bold" /></template>
