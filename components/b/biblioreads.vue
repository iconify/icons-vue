<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ek6gb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-ek6gb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:biblioreads" /></template>
