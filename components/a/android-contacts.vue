<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi50_ecyu.css';
import '../../css/m/my8yzv9ss.css';
import '../../css/l/luip11i6o.css';
import '../../css/d/dj_15obqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fi50_ecyu"/><path class="my8yzv9ss"/><g><path class="luip11i6o"/><path class="dj_15obqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-contacts" /></template>
