<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhz-90b4r.css';
import '../../css/g/gfbw707kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yhz-90b4r"/><path class="gfbw707kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:artstation" /></template>
