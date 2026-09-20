<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp7-0ubcz.css';
import '../../css/l/lxxy901ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wp7-0ubcz"/><circle class="lxxy901ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:eye" /></template>
