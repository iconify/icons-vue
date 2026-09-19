<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8p978b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o8p978b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:html5-wordmark" /></template>
