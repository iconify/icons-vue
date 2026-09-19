<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcin9tbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="vcin9tbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:battery-full" /></template>
