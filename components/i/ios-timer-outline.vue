<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b303i_gmx.css';
import '../../css/s/s70hg-4vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b303i_gmx"/><path class="s70hg-4vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-timer-outline" /></template>
