<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7qt11bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7qt11bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar" /></template>
