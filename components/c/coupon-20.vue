<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl41xxbat.css';
import '../../css/a/a8eh2dnic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tl41xxbat"/><path class="a8eh2dnic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupon-20" /></template>
