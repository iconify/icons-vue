<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js2nh1ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="js2nh1ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docker" /></template>
