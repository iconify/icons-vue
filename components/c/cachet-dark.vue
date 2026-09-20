<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwyj592ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwyj592ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cachet-dark" /></template>
