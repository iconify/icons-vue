<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn76znsys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tn76znsys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cloudflare" /></template>
