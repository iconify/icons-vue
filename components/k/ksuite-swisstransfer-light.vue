<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iedyk4l4k.css';
import '../../css/x/xfes82bvz.css';
import '../../css/r/rzokr9xwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iedyk4l4k"/><path class="xfes82bvz"/><path class="rzokr9xwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-swisstransfer-light" /></template>
