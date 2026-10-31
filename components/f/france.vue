<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9cl-boot.css';
import '../../css/v/v4iotl68y.css';
import '../../css/t/t2w8mls_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="v4iotl68y"/><path class="t2w8mls_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:france" /></template>
