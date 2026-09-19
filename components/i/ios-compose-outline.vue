<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwhq_1bfc.css';
import '../../css/s/s0kb75b8z.css';
import '../../css/z/zyduq6bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwhq_1bfc"/><path class="s0kb75b8z"/><path class="zyduq6bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-compose-outline" /></template>
