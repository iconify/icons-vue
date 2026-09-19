<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05wonbip.css';
import '../../css/c/c913fr9up.css';
import '../../css/c/chcv3v1yb.css';
import '../../css/v/vuehnbe_u.css';
import '../../css/u/ueukz9h4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a05wonbip"/><path class="c913fr9up"/><path class="chcv3v1yb"/><path class="vuehnbe_u"/><path class="ueukz9h4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blacknib" /></template>
