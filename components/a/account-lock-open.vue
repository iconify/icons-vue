<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm-7o-8hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm-7o-8hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-lock-open" /></template>
