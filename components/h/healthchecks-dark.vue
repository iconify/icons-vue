<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm28nkbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm28nkbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthchecks-dark" /></template>
