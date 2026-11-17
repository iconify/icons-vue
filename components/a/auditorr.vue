<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7audcctd.css';
import '../../css/p/pah233ash.css';
import '../../css/w/whx3_cfkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7audcctd"/><path class="pah233ash"/><path class="whx3_cfkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:auditorr" /></template>
