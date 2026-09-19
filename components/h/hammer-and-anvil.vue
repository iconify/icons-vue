<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go04vzgue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="go04vzgue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hammer-and-anvil" /></template>
