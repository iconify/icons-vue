<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p52u5b7hp.css';
import '../../css/f/f7q9a2bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p52u5b7hp"/><path class="f7q9a2bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:close-20" /></template>
