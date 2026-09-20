<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3cao43jn.css';
import '../../css/f/f13cyk52i.css';
import '../../css/s/smok2x2qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3cao43jn"/><path clip-rule="evenodd" class="f13cyk52i"/><path class="smok2x2qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:inbox-post-solid" /></template>
