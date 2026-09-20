<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe2xp6bxc.css';
import '../../css/q/qa72txrwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pe2xp6bxc"/><path class="qa72txrwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fhem" /></template>
