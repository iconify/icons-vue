<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk8f1vb6j.css';
import '../../css/a/ab8l0tjds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tk8f1vb6j"/><path class="ab8l0tjds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:consul-wordmark" /></template>
