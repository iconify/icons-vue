<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9fw8z-ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9fw8z-ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-up-down" /></template>
