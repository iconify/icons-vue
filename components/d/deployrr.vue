<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czy80m__f.css';
import '../../css/o/o94urebay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czy80m__f"/><path class="o94urebay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deployrr" /></template>
