<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4dsqac7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4dsqac7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-information-light" /></template>
