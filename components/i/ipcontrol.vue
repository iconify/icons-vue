<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxt81ccuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gxt81ccuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ipcontrol" /></template>
