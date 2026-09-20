<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_fn9_bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="q_fn9_bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:briefcase" /></template>
