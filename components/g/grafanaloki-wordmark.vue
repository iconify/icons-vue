<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0s9xhb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k0s9xhb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:grafanaloki-wordmark" /></template>
