<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1j20kexv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1j20kexv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:logout3-filled" /></template>
