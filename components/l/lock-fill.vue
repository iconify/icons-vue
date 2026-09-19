<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enk_bkg6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="enk_bkg6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-fill" /></template>
