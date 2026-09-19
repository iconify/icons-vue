<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1rr9jblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="z1rr9jblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hat-cowboy" /></template>
