<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd0jd6bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xd0jd6bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koito-light" /></template>
