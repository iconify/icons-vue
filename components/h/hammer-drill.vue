<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn0-yfbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn0-yfbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hammer-drill" /></template>
