<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwz2ijbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwz2ijbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-medium-02" /></template>
