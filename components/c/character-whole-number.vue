<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9hw_hbtw.css';
import '../../css/j/jej-4abki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v9hw_hbtw"/><path class="jej-4abki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-whole-number" /></template>
