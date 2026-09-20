<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx2mo8b7f.css';
import '../../css/b/bc7209bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vx2mo8b7f"/><path class="bc7209bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:boson" /></template>
