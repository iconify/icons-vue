<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaztqrg0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jaztqrg0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crt-sh-light" /></template>
