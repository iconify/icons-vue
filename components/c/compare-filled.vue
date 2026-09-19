<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anuis4b4o.css';
import '../../css/l/lx9wmlfpv.css';
import '../../css/h/h-rpm9riz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="anuis4b4o b"/><rect class="b lx9wmlfpv"/><path class="b h-rpm9riz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:compare-filled" /></template>
