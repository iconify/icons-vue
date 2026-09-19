<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0ojfxbrx.css';
import '../../css/a/akenjqb-m.css';
import '../../css/a/a7ah0vuxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0ojfxbrx"/><path class="akenjqb-m"/><path class="a7ah0vuxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:gamedie" /></template>
