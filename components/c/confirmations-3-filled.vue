<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhd2w0b6x.css';
import '../../css/a/a8e-e4bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhd2w0b6x"/><path clip-rule="evenodd" class="a8e-e4bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-3-filled" /></template>
