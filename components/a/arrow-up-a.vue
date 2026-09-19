<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfi_23bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfi_23bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-a" /></template>
