<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtggf5bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtggf5bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hold-02" /></template>
