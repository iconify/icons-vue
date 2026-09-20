<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb2wwnbzj.css';
import '../../css/k/kc5z_3btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pb2wwnbzj"/><path class="kc5z_3btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cool" /></template>
