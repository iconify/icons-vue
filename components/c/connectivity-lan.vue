<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_byu8vhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_byu8vhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:connectivity-lan" /></template>
