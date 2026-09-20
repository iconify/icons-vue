<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgh8ogqyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgh8ogqyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-circle-remix" /></template>
