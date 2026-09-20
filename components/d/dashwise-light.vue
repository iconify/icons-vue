<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_k7qbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii_k7qbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dashwise-light" /></template>
