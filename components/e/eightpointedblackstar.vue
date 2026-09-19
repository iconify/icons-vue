<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa7jezu9i.css';
import '../../css/h/hn7rx0huz.css';
import '../../css/z/zavg8fb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sa7jezu9i"/><path class="hn7rx0huz"/><path class="zavg8fb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:eightpointedblackstar" /></template>
