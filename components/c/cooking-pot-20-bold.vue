<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-a_50ber.css';
import '../../css/r/r5y-twbvw.css';
import '../../css/e/e8e0uwbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k-a_50ber"/><path class="r5y-twbvw"/><path class="e8e0uwbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooking-pot-20-bold" /></template>
