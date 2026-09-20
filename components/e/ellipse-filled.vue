<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9m42zb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9m42zb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ellipse-filled" /></template>
