<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aud9bzb6h.css';
import '../../css/x/x4saxe2xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aud9bzb6h"/><path class="x4saxe2xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cog" /></template>
