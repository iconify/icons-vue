<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcr-teb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcr-teb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-broken" /></template>
