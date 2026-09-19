<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj56tdb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wj56tdb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:knob" /></template>
