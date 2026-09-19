<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_zylnsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fj_zylnsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-smile" /></template>
