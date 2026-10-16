<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-wxdblp.css';
import '../../css/e/ewoso7beo.css';
import '../../css/w/wabkd6bsw.css';
import '../../css/j/jwu10ccso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="ewoso7beo"/><path class="wabkd6bsw"/><path class="jwu10ccso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-storage-48" /></template>
