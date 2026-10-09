<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj9306bap.css';
import '../../css/j/jh0o79cyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nj9306bap"/><path class="jh0o79cyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kayak-20-bold" /></template>
