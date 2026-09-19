<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9vaa1ezk.css';
import '../../css/n/nidir5bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9vaa1ezk"/><path class="nidir5bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bell" /></template>
