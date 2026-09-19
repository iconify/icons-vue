<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo1wz-2dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo1wz-2dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up" /></template>
