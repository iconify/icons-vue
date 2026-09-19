<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcvoxpbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="vcvoxpbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fbdislike" /></template>
