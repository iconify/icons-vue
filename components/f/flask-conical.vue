<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lke22-_uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lke22-_uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flask-conical" /></template>
