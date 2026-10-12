<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur3m-8djy.css';
import '../../css/u/uvv6a-b1c.css';
import '../../css/u/ul72h2brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ur3m-8djy"/><path class="uvv6a-b1c"/><path class="ul72h2brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lathe-20" /></template>
