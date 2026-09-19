<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbfje_oxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cbfje_oxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-spread" /></template>
