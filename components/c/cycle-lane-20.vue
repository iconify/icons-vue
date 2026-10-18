<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er8a602go.css';
import '../../css/w/w6rk5mb9y.css';
import '../../css/d/df5c527xr.css';
import '../../css/q/qt3qyac8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="er8a602go"/><path class="w6rk5mb9y"/><path class="df5c527xr"/><path class="qt3qyac8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cycle-lane-20" /></template>
