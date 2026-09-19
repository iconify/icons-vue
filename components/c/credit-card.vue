<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2_zngbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="a2_zngbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:credit-card" /></template>
