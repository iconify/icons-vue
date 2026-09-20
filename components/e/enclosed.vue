<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt7xkpbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rt7xkpbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:enclosed" /></template>
