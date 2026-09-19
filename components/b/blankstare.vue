<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxuw8rb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bxuw8rb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:blankstare" /></template>
