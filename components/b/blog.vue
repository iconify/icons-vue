<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwskhw6wu.css';
import '../../css/j/jmbniybow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vwskhw6wu"/><path class="jmbniybow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:blog" /></template>
