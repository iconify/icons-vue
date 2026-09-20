<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3jke53fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y3jke53fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:attraction" /></template>
