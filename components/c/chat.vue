<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr7o5cr9r.css';
import '../../css/x/xv07l8uxa.css';
import '../../css/u/u85qrgbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="lr7o5cr9r"/><path clip-rule="evenodd" class="xv07l8uxa"/><path class="u85qrgbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:chat" /></template>
