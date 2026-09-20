<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7cbi6b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u7cbi6b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-under-barbed-hook" /></template>
