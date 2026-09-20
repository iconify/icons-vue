<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uonq2q-9z.css';
import '../../css/w/w-n1usl-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uonq2q-9z"/><path class="w-n1usl-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:deno" /></template>
