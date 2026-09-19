<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axyfo5byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axyfo5byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-bottom-02" /></template>
