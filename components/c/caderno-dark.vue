<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6jf7lbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t6jf7lbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caderno-dark" /></template>
