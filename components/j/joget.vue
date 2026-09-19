<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb0p2xp2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="zb0p2xp2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:joget" /></template>
