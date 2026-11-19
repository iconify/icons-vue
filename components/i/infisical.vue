<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6gs6rbtb.css';
import '../../css/m/mf-rqbcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j6gs6rbtb"/><path class="mf-rqbcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:infisical" /></template>
