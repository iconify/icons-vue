<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czw79453b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="czw79453b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:kubernetes-wordmark" /></template>
