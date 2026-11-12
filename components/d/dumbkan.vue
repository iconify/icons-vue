<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_pu1d1nt.css';
import '../../css/x/xifkqvb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="e_pu1d1nt"/><path class="xifkqvb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbkan" /></template>
