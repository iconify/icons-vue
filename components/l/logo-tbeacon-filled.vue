<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scsbkobgd.css';
import '../../css/r/ro_92tjwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scsbkobgd"/><path class="ro_92tjwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tbeacon-filled" /></template>
