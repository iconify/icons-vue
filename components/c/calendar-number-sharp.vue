<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta9oqnbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ta9oqnbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:calendar-number-sharp" /></template>
