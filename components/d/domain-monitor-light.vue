<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iitdx4b4n.css';
import '../../css/e/egm87yb8i.css';
import '../../css/o/oen_blbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iitdx4b4n"/><path class="egm87yb8i"/><path class="oen_blbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-monitor-light" /></template>
