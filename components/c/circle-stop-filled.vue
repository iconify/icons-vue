<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qahyg6byo.css';
import '../../css/u/uyt0x-bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qahyg6byo"/><path clip-rule="evenodd" class="uyt0x-bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-stop-filled" /></template>
