<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnjy4wpbq.css';
import '../../css/l/lxrsy8bdk.css';
import '../../css/g/ga3lzib3e.css';
import '../../css/n/njhb20v1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnjy4wpbq"/><path class="lxrsy8bdk"/><path class="ga3lzib3e"/><path clip-rule="evenodd" class="njhb20v1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-wink-plus-solid" /></template>
