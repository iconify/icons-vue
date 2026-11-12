<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2dqk2sur.css';
import '../../css/r/rb6k0dd7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2dqk2sur"/><path class="rb6k0dd7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster" /></template>
