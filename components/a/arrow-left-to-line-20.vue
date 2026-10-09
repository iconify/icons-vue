<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhl8dp5hn.css';
import '../../css/n/nb9mp9bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zhl8dp5hn"/><path class="nb9mp9bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-to-line-20" /></template>
