<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p777b5bsc.css';
import '../../css/i/iic8aijvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p777b5bsc"/><path class="iic8aijvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:intercom" /></template>
