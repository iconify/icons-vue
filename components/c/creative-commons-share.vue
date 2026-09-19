<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr6b--b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="sr6b--b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:creative-commons-share" /></template>
