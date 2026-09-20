<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwdbhvfaz.css';
import '../../css/x/xj-vmnbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwdbhvfaz"/><path class="xj-vmnbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ggg" /></template>
