<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiu1hih7a.css';
import '../../css/c/cjifcyb7a.css';
import '../../css/p/pvmf4ib9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiu1hih7a"/><path class="cjifcyb7a"/><path class="pvmf4ib9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:haka" /></template>
