<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8pfxrb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8pfxrb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-dark" /></template>
