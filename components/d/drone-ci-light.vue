<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-u70hkkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-u70hkkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:drone-ci-light" /></template>
