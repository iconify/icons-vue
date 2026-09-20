<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9fx__esr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z9fx__esr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-collar-and-heart" /></template>
