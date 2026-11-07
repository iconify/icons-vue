<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfi9t8bxj.css';
import '../../css/z/zw-inltah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfi9t8bxj"/><path class="zw-inltah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-outline" /></template>
