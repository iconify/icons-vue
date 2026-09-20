<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om201sw6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="om201sw6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dial-pad-finger-2-remix" /></template>
