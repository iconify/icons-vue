<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm5ogkonw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jm5ogkonw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:concierge-bell" /></template>
