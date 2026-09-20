<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlw4881-w.css';
import '../../css/f/fp5wvo1sn.css';
import '../../css/w/wwbd329qt.css';
import '../../css/h/hii85eizm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zlw4881-w"/><path class="fp5wvo1sn"/><path class="wwbd329qt"/><path class="hii85eizm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:joomla" /></template>
