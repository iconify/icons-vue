<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-3d572jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-3d572jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-up-from-square" /></template>
