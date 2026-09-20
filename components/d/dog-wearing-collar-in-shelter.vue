<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4gv7gz6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q4gv7gz6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-wearing-collar-in-shelter" /></template>
