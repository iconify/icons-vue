<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt1np09fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tt1np09fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:countdown-timer" /></template>
