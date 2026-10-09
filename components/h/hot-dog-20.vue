<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv3c1ol4t.css';
import '../../css/y/yx--xhf4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lv3c1ol4t"/><path class="yx--xhf4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-dog-20" /></template>
