<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj5vzgbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vj5vzgbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flood-dark" /></template>
