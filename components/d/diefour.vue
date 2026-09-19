<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdv30hu3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":959};
const content = `<path class="tdv30hu3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:diefour" /></template>
