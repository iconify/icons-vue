<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8czseb2v.css';
import '../../css/u/uoo_ldb1e.css';
import '../../css/d/d-xw4ab1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="uoo_ldb1e"/><path class="d-xw4ab1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-ring-bold-duotone" /></template>
