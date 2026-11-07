<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8czseb2v.css';
import '../../css/u/uoo_ldb1e.css';
import '../../css/h/h03wxzbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="uoo_ldb1e"/><path class="h03wxzbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-off-bold-duotone" /></template>
