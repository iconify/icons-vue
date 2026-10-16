<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzc1gb6wy.css';
import '../../css/q/qvjlz2b3k.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzc1gb6wy"/><path class="qvjlz2b3k"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chemical-plant-20-bold" /></template>
