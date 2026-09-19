<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq75i1y9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq75i1y9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-female" /></template>
