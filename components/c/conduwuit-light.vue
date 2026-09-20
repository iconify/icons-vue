<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihiv9sbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihiv9sbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduwuit-light" /></template>
