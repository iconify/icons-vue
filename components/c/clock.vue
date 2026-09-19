<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci31p8bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ci31p8bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:clock" /></template>
