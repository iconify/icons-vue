<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm_nw-iud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zm_nw-iud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cancel2x-outline" /></template>
