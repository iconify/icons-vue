<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6ovpccxr.css';
import '../../css/q/qume8ab4m.css';
import '../../css/i/itc5zdbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="p6ovpccxr"/><path class="qume8ab4m"/><g><path class="itc5zdbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-information-outline" /></template>
