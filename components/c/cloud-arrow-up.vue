<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcuf-ab3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tcuf-ab3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-arrow-up" /></template>
