<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7k8fqbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="c7k8fqbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:link-horizontal" /></template>
