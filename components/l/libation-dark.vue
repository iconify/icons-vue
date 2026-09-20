<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk1khyh6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk1khyh6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libation-dark" /></template>
