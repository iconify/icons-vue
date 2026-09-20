<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv9oo8zrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv9oo8zrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lastpass-dark" /></template>
