<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_avxy5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kc_avxy5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-point-up" /></template>
