<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4fj4wl6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4fj4wl6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arlo-dark" /></template>
