<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpzy0bbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rpzy0bbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-upper-case" /></template>
