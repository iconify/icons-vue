<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8a77rbjy.css';
import '../../css/g/gh2npccpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8a77rbjy"/><path class="gh2npccpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-swap" /></template>
