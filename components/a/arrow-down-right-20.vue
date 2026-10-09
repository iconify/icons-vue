<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p52u5b7hp.css';
import '../../css/l/l9thhtagt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p52u5b7hp"/><path class="l9thhtagt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-right-20" /></template>
