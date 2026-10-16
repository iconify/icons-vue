<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6veld26c.css';
import '../../css/u/u_6gs2b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y6veld26c"/><path class="u_6gs2b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dosimeter-20" /></template>
