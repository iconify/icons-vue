<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqromeb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nqromeb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-pointer" /></template>
