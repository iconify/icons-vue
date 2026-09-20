<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/autdh0b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="autdh0b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agam-space-light" /></template>
