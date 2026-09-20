<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o54po1hhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o54po1hhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermes-agent-light" /></template>
