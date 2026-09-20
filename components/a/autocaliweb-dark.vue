<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0d7aqnpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0d7aqnpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autocaliweb-dark" /></template>
