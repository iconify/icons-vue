<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr-9vqbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wr-9vqbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:globe-gasoline-pump-with-e" /></template>
