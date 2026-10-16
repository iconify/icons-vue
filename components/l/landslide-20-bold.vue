<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5hn9ec-l.css';
import '../../css/r/r_ps52b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z5hn9ec-l"/><path class="r_ps52b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landslide-20-bold" /></template>
