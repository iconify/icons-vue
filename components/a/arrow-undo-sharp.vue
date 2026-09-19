<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujp3zn38v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujp3zn38v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-undo-sharp" /></template>
