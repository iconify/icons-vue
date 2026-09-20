<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/k/k__vmq.css';
import '../../css/r/rje0ii.css';
import '../../css/u/ul_dtz.css';
import '../../css/e/e7acus.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c k__vmq"/><path class="a0m25c rje0ii"/><path class="a0m25c ul_dtz"/><path class="a0m25c e7acus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:emoji-smile" /></template>
