<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2q3hbarl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2q3hbarl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubero-light" /></template>
