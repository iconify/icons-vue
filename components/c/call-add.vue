<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbuc_wbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbuc_wbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-add" /></template>
