<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6s5kw3-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6s5kw3-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-fan-1" /></template>
