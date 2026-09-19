<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djlse4bnq.css';
import '../../css/c/c8xjk5bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djlse4bnq"/><path class="c8xjk5bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bonfire" /></template>
