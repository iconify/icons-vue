<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0vf9bvy.css';
import '../../css/e/ec1om73-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="ec1om73-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:induction-hob-20" /></template>
