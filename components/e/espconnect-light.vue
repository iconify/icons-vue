<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rok_s9ahy.css';
import '../../css/b/b4_i_1h2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rok_s9ahy"/><path class="b4_i_1h2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espconnect-light" /></template>
