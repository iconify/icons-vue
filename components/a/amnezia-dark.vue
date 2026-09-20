<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to735iv_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="to735iv_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amnezia-dark" /></template>
