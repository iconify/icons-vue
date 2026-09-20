<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz5smomfx.css';
import '../../css/p/p8s9m2bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oz5smomfx"/><path class="p8s9m2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:glass-soda-16" /></template>
