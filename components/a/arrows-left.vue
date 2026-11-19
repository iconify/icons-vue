<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev_uos1kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev_uos1kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-left" /></template>
