<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hamm36bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hamm36bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-phone-portrait" /></template>
