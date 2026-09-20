<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikxd3jb2y.css';
import '../../css/b/b3ex35ova.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikxd3jb2y"/><path class="b3ex35ova"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitea" /></template>
