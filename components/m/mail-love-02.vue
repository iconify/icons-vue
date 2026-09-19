<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xdw8tmbkh.css';
import '../../css/b/bjv2qsbby.css';
import '../../css/m/mjfpkub2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xdw8tmbkh"/><path class="bjv2qsbby"/><path class="mjfpkub2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-love-02" /></template>
