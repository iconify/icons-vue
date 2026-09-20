<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkz36vbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="dkz36vbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:jet-skiing" /></template>
