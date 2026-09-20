<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk1cacbgq.css';
import '../../css/w/whi2f_bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="bk1cacbgq"/><path class="whi2f_bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:island-2" /></template>
