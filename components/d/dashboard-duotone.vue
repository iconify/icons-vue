<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcfaj0bdj.css';
import '../../css/c/c7b0ob2tk.css';
import '../../css/r/rcidtuiap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcfaj0bdj"/><path class="c7b0ob2tk"/><path class="rcidtuiap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:dashboard-duotone" /></template>
