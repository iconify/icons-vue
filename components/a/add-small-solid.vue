<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evfk3vb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="evfk3vb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:add-small-solid" /></template>
