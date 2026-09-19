<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvw4z98pg.css';
import '../../css/l/luchnh4nb.css';
import '../../css/p/p0dnb-b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="wvw4z98pg"/><circle class="luchnh4nb"/><path class="p0dnb-b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:image-outline" /></template>
