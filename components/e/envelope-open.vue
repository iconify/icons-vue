<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y864t2bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y864t2bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:envelope-open" /></template>
