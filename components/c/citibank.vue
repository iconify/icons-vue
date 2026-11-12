<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il552bv-l.css';
import '../../css/u/uzxqaob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il552bv-l"/><path class="uzxqaob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:citibank" /></template>
