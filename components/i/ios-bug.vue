<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjkt4fvdh.css';
import '../../css/j/jswt5rbrt.css';
import '../../css/u/um2_m_i-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjkt4fvdh"/><path class="jswt5rbrt"/><path class="um2_m_i-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bug" /></template>
