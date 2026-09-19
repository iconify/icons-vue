<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atoj6abie.css';
import '../../css/y/yo0y45bgr.css';
import '../../css/v/vcmsx7koy.css';
import '../../css/g/gsi6ambhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="atoj6abie"/><path class="yo0y45bgr"/><path class="vcmsx7koy"/><path class="gsi6ambhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-toggle" /></template>
