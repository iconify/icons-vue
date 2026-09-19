<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmurddcry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zmurddcry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:balance-scale-right" /></template>
