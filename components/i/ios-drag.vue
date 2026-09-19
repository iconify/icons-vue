<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6bn8gzzq.css';
import '../../css/y/yo7ggd95z.css';
import '../../css/a/a1qd-mzwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g6bn8gzzq"/><path class="yo7ggd95z"/><path class="a1qd-mzwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-drag" /></template>
