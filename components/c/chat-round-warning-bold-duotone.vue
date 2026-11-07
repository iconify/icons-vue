<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0jc9qlwi.css';
import '../../css/q/qsm1dmd4a.css';
import '../../css/z/z04quez4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc9qlwi"/><path class="qsm1dmd4a"/><path class="z04quez4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-warning-bold-duotone" /></template>
