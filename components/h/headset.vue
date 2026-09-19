<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvlzrldrv.css';
import '../../css/b/b8lwwppwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvlzrldrv"/><path class="b8lwwppwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:headset" /></template>
