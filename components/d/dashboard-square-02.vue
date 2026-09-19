<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5_s5-uqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5_s5-uqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-square-02" /></template>
