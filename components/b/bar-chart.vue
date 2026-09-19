<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd1nwx7pc.css';
import '../../css/b/bp0flui-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd1nwx7pc"/><path class="bp0flui-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bar-chart" /></template>
