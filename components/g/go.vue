<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcwudk0gy.css';
import '../../css/s/sn54l82wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcwudk0gy"/><path class="sn54l82wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:go" /></template>
