<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/n/ne92tx4kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="ne92tx4kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:explicit-bold-duotone" /></template>
