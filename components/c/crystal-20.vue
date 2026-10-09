<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juwx635fx.css';
import '../../css/y/yx8h1eeun.css';
import '../../css/y/yvxmkpbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="juwx635fx"/><path class="yx8h1eeun"/><path class="yvxmkpbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crystal-20" /></template>
