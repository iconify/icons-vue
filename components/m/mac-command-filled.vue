<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to8dx_b8t.css';
import '../../css/x/x0n0x1bdz.css';
import '../../css/f/f_lfe3b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="to8dx_b8t"/><path class="x0n0x1bdz"/><path class="f_lfe3b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mac-command-filled" /></template>
