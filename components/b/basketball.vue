<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiq6z9xnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kiq6z9xnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:basketball" /></template>
