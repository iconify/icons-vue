<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v412_cb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v412_cb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:eye-closed-solid" /></template>
