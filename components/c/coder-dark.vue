<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzw0sac3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzw0sac3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coder-dark" /></template>
