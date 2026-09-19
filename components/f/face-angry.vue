<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa-q0hbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aa-q0hbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-angry" /></template>
