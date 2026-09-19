<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic4fhhbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="ic4fhhbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:amex" /></template>
