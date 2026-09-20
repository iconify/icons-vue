<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhakt415t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhakt415t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haptic-dark" /></template>
