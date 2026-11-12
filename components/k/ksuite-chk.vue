<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx1ed53-h.css';
import '../../css/k/kmzi6e6ft.css';
import '../../css/j/josq1jb8s.css';
import '../../css/y/yjwzayklo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx1ed53-h"/><path class="kmzi6e6ft"/><path class="josq1jb8s"/><path class="yjwzayklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-chk" /></template>
