<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljbt1k0jq.css';
import '../../css/a/ag3j1zb_c.css';
import '../../css/i/i5nh8nifr.css';
import '../../css/q/qurxc7b-j.css';
import '../../css/m/mho7osb0z.css';
import '../../css/q/qlsbzj3nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ljbt1k0jq"/><path class="ag3j1zb_c"/><path class="i5nh8nifr"/><circle class="qurxc7b-j"/><circle class="mho7osb0z"/><circle class="qlsbzj3nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chats" /></template>
