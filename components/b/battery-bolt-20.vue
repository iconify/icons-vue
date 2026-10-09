<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdbcpwbxd.css';
import '../../css/z/zso3njb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qdbcpwbxd"/><path class="zso3njb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-bolt-20" /></template>
