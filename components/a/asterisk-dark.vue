<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6057zb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6057zb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asterisk-dark" /></template>
