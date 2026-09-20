<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q49_fbchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5.5,"top":-2};
const content = `<path class="q49_fbchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:building-f" /></template>
