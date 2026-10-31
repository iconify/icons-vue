<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw4rygbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bw4rygbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building" /></template>
