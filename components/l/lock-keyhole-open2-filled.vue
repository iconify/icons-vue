<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqaqp2cek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqaqp2cek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-keyhole-open2-filled" /></template>
