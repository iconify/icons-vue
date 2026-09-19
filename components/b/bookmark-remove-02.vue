<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvw95zb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvw95zb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-remove-02" /></template>
