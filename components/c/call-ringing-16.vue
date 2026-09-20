<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf_jb02lk.css';
import '../../css/v/v3xgw3bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wf_jb02lk"/><path class="v3xgw3bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-ringing-16" /></template>
