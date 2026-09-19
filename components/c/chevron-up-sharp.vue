<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skz155b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skz155b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-up-sharp" /></template>
