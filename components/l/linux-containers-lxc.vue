<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usuimpbio.css';
import '../../css/i/i5007011u.css';
import '../../css/m/mh0n59bar.css';
import '../../css/g/gyydhabtl.css';
import '../../css/t/tkbog5bpr.css';
import '../../css/j/j--d0i75f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usuimpbio"/><path class="i5007011u"/><path class="mh0n59bar"/><path class="gyydhabtl"/><path class="tkbog5bpr"/><path class="j--d0i75f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-containers-lxc" /></template>
