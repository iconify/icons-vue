<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enb9o6bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enb9o6bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:checkmark-circle-checked-solid" /></template>
