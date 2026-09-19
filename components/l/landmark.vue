<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqn56fbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqn56fbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:landmark" /></template>
