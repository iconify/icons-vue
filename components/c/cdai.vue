<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlfgvwzg.css';
import '../../css/m/m8sb_hy9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlfgvwzg"/><path clip-rule="evenodd" class="m8sb_hy9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cdai" /></template>
