<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmm71acjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmm71acjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:dumbbell" /></template>
