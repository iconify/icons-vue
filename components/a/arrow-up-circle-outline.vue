<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b49iidcfv.css';
import '../../css/l/lsg5j7ibl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b49iidcfv"/><path class="lsg5j7ibl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-circle-outline" /></template>
