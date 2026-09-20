<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/p8y04bble.css';
import '../../css/r/r6wv0301c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="p8y04bble"/><path class="r6wv0301c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-check" /></template>
