<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sasmg8j9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sasmg8j9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-three" /></template>
