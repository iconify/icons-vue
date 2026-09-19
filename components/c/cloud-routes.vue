<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd_3bbbwk.css';
import '../../css/w/w5hpaebnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd_3bbbwk"/><path class="w5hpaebnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-routes" /></template>
