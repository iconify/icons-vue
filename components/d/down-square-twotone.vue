<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8-4tb2b.css';
import '../../css/s/s6f_wmmxy.css';
import '../../css/y/ypremix2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="s6f_wmmxy"/><path class="ypremix2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:down-square-twotone" /></template>
