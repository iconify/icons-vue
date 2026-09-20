<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdcc6fbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdcc6fbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fubotv-dark" /></template>
