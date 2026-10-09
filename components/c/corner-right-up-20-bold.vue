<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewh_gkbzz.css';
import '../../css/g/gjv7hdb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewh_gkbzz"/><path class="gjv7hdb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-up-20-bold" /></template>
