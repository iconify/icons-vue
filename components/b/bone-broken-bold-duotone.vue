<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itet59rhp.css';
import '../../css/k/kdn9gsbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itet59rhp"/><path class="kdn9gsbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-broken-bold-duotone" /></template>
