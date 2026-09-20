<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmjlqurpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmjlqurpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:copyparty-light" /></template>
