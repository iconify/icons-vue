<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-opoeb5s.css';
import '../../css/k/k4cnuob7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="m-opoeb5s"/><path class="k4cnuob7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:firefox-wordmark" /></template>
