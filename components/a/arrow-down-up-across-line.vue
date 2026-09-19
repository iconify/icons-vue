<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ovedbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="z9ovedbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-up-across-line" /></template>
