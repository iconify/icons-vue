<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em9miyxzj.css';
import '../../css/v/v4i2ew1ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em9miyxzj"/><circle class="v4i2ew1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-radiation" /></template>
