<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8p4fabkp.css';
import '../../css/d/d_g8hik9b.css';
import '../../css/d/d4yobybuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8p4fabkp"/><path class="d_g8hik9b"/><path class="d4yobybuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-designernews-outline" /></template>
