<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhlp3bxm.css';
import '../../css/w/wgaj_ib1j.css';
import '../../css/s/s07htpbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzhlp3bxm"/><path class="wgaj_ib1j"/><path class="s07htpbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bullseye" /></template>
