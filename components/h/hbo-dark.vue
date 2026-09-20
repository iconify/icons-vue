<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km37tmb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="km37tmb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hbo-dark" /></template>
