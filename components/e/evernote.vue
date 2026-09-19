<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq1o3oben.css';
import '../../css/q/qzsos-3ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iq1o3oben"/><path class="qzsos-3ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:evernote" /></template>
