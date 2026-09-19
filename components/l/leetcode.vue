<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvlx87bnz.css';
import '../../css/e/eud0165so.css';
import '../../css/b/bpxdh911r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xvlx87bnz"/><path class="eud0165so"/><path class="bpxdh911r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:leetcode" /></template>
