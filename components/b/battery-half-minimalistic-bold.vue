<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge4dfdclf.css';
import '../../css/q/qfc_s602x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge4dfdclf"/><path class="qfc_s602x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-half-minimalistic-bold" /></template>
