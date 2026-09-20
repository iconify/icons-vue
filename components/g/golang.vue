<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmgdm_xko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmgdm_xko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:golang" /></template>
