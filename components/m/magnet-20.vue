<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvc1jlbnu.css';
import '../../css/j/juittjbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvc1jlbnu"/><path class="juittjbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magnet-20" /></template>
