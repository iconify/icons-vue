<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njc-z_btr.css';
import '../../css/k/kiohhd3cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njc-z_btr"/><path clip-rule="evenodd" class="kiohhd3cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:assignment-fill" /></template>
