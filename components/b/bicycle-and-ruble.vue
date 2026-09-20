<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inwf89b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="inwf89b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-ruble" /></template>
