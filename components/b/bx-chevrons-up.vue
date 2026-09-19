<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkpiz7yuq.css';
import '../../css/x/xh52_lwgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkpiz7yuq"/><path class="xh52_lwgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chevrons-up" /></template>
