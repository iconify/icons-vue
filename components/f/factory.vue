<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75xp5i-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="q75xp5i-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:factory" /></template>
