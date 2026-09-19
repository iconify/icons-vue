<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmbc4zpnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="kmbc4zpnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:lab" /></template>
