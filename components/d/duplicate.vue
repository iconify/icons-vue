<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5rhcysgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5rhcysgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:duplicate" /></template>
