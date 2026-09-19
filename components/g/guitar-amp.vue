<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojnmpz68t.css';
import '../../css/j/jsoljj9wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnmpz68t"/><path class="jsoljj9wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:guitar-amp" /></template>
