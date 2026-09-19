<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_zctbc7m.css';
import '../../css/j/jw5g59skx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zctbc7m"/><path class="jw5g59skx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:critical-bug-outlined" /></template>
