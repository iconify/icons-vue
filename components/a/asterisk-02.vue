<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmojuv_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmojuv_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:asterisk-02" /></template>
