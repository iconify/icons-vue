<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwdr8__0e.css';
import '../../css/x/xkhbux-bb.css';
import '../../css/d/dk28xybqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwdr8__0e"/><path clip-rule="evenodd" class="xkhbux-bb"/><path class="dk28xybqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:container-bold" /></template>
