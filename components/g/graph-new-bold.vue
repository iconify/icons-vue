<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri62nr2ps.css';
import '../../css/s/siai_tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ri62nr2ps"/><path class="siai_tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-new-bold" /></template>
