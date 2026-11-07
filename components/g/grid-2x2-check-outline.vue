<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln-hxshjc.css';
import '../../css/e/egi_o9bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln-hxshjc"/><path class="egi_o9bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-check-outline" /></template>
