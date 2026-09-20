<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naw5s4b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="naw5s4b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-light" /></template>
