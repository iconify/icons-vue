<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf6tnbc7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nf6tnbc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dependabot-wordmark" /></template>
