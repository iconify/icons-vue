<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smscfqy7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smscfqy7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forms-md-light" /></template>
