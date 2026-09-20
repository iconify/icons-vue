<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqglnrb0z.css';
import '../../css/s/s6o6votsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wqglnrb0z"/><path clip-rule="evenodd" class="s6o6votsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bank-solid" /></template>
