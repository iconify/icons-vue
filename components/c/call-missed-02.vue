<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d52muybuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d52muybuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-missed-02" /></template>
