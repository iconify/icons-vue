<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iey856b5w.css';
import '../../css/a/aelxiub-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iey856b5w"/><path class="aelxiub-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:chalkboard" /></template>
