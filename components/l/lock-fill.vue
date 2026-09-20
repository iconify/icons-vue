<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc1ytd_oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc1ytd_oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lock-fill" /></template>
