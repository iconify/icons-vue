<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5h7piywn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5h7piywn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-off-sharp" /></template>
