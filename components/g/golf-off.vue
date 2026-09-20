<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6z3wwxoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6z3wwxoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:golf-off" /></template>
