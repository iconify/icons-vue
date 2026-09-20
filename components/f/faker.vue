<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2e3_cb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2e3_cb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:faker" /></template>
