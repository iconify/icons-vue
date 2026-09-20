<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo2r4y9hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo2r4y9hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authentik-dark" /></template>
