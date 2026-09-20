<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm56libzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pm56libzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agent-zero-dark" /></template>
