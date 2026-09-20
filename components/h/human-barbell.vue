<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdd7jibvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdd7jibvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-barbell" /></template>
