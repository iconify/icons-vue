<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpdbmfbhr.css';
import '../../css/i/i6oim-fty.css';
import '../../css/n/n30ul-b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="dpdbmfbhr"/><path class="i6oim-fty"/><path class="n30ul-b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:actual-mcp-server" /></template>
