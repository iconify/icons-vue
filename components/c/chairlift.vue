<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h88y73pra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="h88y73pra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:chairlift" /></template>
