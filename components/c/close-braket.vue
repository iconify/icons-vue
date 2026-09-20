<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcg0lcc6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="lcg0lcc6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:close-braket" /></template>
