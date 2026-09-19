<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul1s29bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ul1s29bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-sad-cry" /></template>
