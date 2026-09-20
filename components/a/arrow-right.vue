<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/t/t6cvhn.css';
import '../../css/q/q3l5np.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c t6cvhn"/><path class="a0m25c q3l5np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-right" /></template>
