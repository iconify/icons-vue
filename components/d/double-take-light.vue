<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9gb9bbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9gb9bbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:double-take-light" /></template>
