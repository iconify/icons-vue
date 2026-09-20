<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez5k8sbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez5k8sbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:command" /></template>
