<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6vz2xq0h.css';
import '../../css/i/ii-9vg1fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6vz2xq0h"/><path class="ii-9vg1fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lock-checked-filled" /></template>
