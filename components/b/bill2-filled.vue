<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmbd_tb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmbd_tb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill2-filled" /></template>
