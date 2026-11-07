<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7x-xvbro.css';
import '../../css/s/siai_tb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7x-xvbro"/><path class="siai_tb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-new-up-bold" /></template>
