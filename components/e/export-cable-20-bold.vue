<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcim_2ucb.css';
import '../../css/a/amu1h0n4r.css';
import '../../css/p/pgvjdacxw.css';
import '../../css/g/ghp9deben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xcim_2ucb"/><path class="amu1h0n4r"/><path class="pgvjdacxw"/><path class="ghp9deben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:export-cable-20-bold" /></template>
