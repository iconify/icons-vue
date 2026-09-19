<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r9ixvp21u.css';
import '../../css/m/mlndmdfps.css';
import '../../css/p/p3m8cmtdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r9ixvp21u"/><path class="mlndmdfps"/><path class="p3m8cmtdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-unlock-02" /></template>
