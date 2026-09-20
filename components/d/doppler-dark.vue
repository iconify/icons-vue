<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb-sgdzxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb-sgdzxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doppler-dark" /></template>
