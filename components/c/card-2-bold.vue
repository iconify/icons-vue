<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5nysxzsm.css';
import '../../css/b/bftzabcak.css';
import '../../css/z/zhscj931y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5nysxzsm"/><path clip-rule="evenodd" class="bftzabcak"/><path class="zhscj931y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-2-bold" /></template>
