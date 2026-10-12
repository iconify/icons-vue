<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5knpcbeg.css';
import '../../css/r/rqr606bgh.css';
import '../../css/t/t3muc1b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e5knpcbeg"/><path class="rqr606bgh"/><path class="t3muc1b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-cycle-fill-20" /></template>
