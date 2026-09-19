<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnoirdb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnoirdb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:compare-states" /></template>
