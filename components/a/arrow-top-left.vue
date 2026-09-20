<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrq3zdb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mrq3zdb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-top-left" /></template>
