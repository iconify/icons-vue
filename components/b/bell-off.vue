<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn-xy7bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn-xy7bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-off" /></template>
