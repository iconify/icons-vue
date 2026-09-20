<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm8sp9grg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vm8sp9grg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atuin-dark" /></template>
