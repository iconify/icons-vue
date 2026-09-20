<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m02shab3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m02shab3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookhaven" /></template>
