<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo-9dz_1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="oo-9dz_1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fridge" /></template>
