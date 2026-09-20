<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8pkmtbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8pkmtbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kagi-dark" /></template>
