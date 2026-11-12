<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzx8rqbxg.css';
import '../../css/q/quscitu3w.css';
import '../../css/i/iv7xugjxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzx8rqbxg"/><path class="quscitu3w"/><path class="iv7xugjxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heyform" /></template>
