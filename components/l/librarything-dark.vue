<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gity0fb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gity0fb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librarything-dark" /></template>
