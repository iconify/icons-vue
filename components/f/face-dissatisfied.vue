<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww4fyqbuj.css';
import '../../css/b/b4hv47bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ww4fyqbuj"/><path class="b4hv47bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-dissatisfied" /></template>
