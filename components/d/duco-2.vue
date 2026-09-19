<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnndvsa8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnndvsa8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duco-2" /></template>
