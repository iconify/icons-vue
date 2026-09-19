<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7_oyuzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xz7_oyuzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:bell-slash" /></template>
