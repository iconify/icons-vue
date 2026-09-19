<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fieqwcbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="fieqwcbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-account" /></template>
