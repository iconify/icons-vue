<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a09o_zzmo.css';
import '../../css/c/ckct19qqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a09o_zzmo"/><path class="ckct19qqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:first-aid" /></template>
