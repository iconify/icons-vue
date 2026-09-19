<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t18nv0b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t18nv0b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:balance-scale-left" /></template>
