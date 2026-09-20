<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpuz2vn1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cpuz2vn1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:application-screens" /></template>
