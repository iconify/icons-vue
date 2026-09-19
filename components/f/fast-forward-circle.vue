<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwibdw4bb.css';
import '../../css/y/ynj1yft6n.css';
import '../../css/x/x6pvdjbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="ynj1yft6n"/><path class="x6pvdjbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fast-forward-circle" /></template>
