<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljx1946ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljx1946ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-open-fill" /></template>
