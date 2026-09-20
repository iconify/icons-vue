<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/j/j7gn8qbkp.css';
import '../../css/j/jvuj7v2wp.css';
import '../../css/g/gg2p7cbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j7gn8qbkp"/><path clip-rule="evenodd" class="jvuj7v2wp"/><path class="gg2p7cbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:american-express-logo" /></template>
