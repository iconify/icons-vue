<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztd9aub4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztd9aub4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-disabled-02" /></template>
