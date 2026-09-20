<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3sh27b1i.css';
import '../../css/w/wln7gbc4q.css';
import '../../css/b/bk_8nxb5u.css';
import '../../css/i/iswi7r7vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3sh27b1i"/><path class="wln7gbc4q"/><path class="bk_8nxb5u"/><path class="iswi7r7vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:css3" /></template>
