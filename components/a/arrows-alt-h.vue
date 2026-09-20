<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcksdoptn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rcksdoptn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrows-alt-h" /></template>
