<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwl3ap3ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwl3ap3ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elysian-light" /></template>
