<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1jnopb3d.css';
import '../../css/l/l3z28ebpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w1jnopb3d"/><path class="l3z28ebpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bug-outline" /></template>
