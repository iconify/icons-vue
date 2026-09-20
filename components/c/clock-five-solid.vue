<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br110rk8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br110rk8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-five-solid" /></template>
