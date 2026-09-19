<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf2_v_89r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vf2_v_89r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bitcoinalt" /></template>
