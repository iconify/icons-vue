<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvezwc7ew.css';
import '../../css/u/uemg9fbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvezwc7ew"/><path class="uemg9fbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:database-filled" /></template>
