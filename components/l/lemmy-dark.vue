<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x734hcp_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x734hcp_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lemmy-dark" /></template>
