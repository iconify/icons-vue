<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6cs2jcph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6cs2jcph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chopsticks-crossed" /></template>
