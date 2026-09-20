<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1fanqb7g.css';
import '../../css/h/hxd1rr2uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1fanqb7g"/><path class="hxd1rr2uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grs" /></template>
