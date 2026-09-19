<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n0o-7rbtu.css';
import '../../css/v/vuvruhbaa.css';
import '../../css/f/f3gxddcxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n0o-7rbtu"/><circle class="vuvruhbaa"/><path class="f3gxddcxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:caravan" /></template>
