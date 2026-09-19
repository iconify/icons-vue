<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p3m8cmtdy.css';
import '../../css/r/r9ixvp21u.css';
import '../../css/p/po3o6yboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p3m8cmtdy"/><path class="r9ixvp21u"/><path class="po3o6yboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-lock-02" /></template>
