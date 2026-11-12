<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix-pf_jrx.css';
import '../../css/s/s8ttcqbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix-pf_jrx"/><path class="s8ttcqbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubernetes" /></template>
